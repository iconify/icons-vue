<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wz9ucbcni.css';
import '../../css/g/g7k394syz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="wz9ucbcni"/><path class="g7k394syz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:speaker" /></template>
