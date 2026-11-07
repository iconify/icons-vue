<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dciv8jbgc.css';
import '../../css/z/zo2kgwbhm.css';
import '../../css/h/hd5dgobzc.css';
import '../../css/k/kyfybbbty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dciv8jbgc"/><path class="zo2kgwbhm"/><path class="hd5dgobzc"/><path clip-rule="evenodd" class="kyfybbbty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:suitcase-tag-bold-duotone" /></template>
