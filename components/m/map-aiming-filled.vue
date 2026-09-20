<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wm1o5wb2q.css';
import '../../css/n/n5z0o6g9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wm1o5wb2q"/><path class="n5z0o6g9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:map-aiming-filled" /></template>
