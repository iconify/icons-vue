<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ea5qyqbox.css';
import '../../css/d/dt2gkbchm.css';
import '../../css/v/vhwau7bwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ea5qyqbox wm-a"/><path class="dt2gkbchm wm-k"/><path class="vhwau7bwl wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:route" /></template>
