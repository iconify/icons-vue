<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbb_qacmw.css';
import '../../css/o/ogxmpc7da.css';
import '../../css/x/xhzi8ovuc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bbb_qacmw"/><path class="ogxmpc7da"/><path class="xhzi8ovuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:puzzle-piece" /></template>
