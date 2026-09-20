<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vg_zrkbvf.css';
import '../../css/j/j525vvb7b.css';
import '../../css/s/s9rtedbwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vg_zrkbvf"/><path class="j525vvb7b"/><path class="s9rtedbwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:stack-24" /></template>
