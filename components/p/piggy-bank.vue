<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wm-3rccze.css';
import '../../css/h/h3fdh8ipt.css';
import '../../css/f/fbp3cgb3s.css';
import '../../css/a/aftd3mbeu.css';
import '../../css/e/eere0mbbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wm-3rccze wm-k"/><path class="h3fdh8ipt wm-k"/><path class="fbp3cgb3s wm-a"/><path class="aftd3mbeu wm-a"/><path class="eere0mbbf wm-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:piggy-bank" /></template>
