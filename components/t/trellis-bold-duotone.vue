<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4-mns66q.css';
import '../../css/c/c52keb9qe.css';
import '../../css/x/x8znsxq4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z4-mns66q"/><path class="c52keb9qe"/><path clip-rule="evenodd" class="x8znsxq4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:trellis-bold-duotone" /></template>
