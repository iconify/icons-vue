<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ax45mqb4h.css';
import '../../css/i/i6wr-kbqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ax45mqb4h"/><path class="i6wr-kbqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:unlock-outline" /></template>
