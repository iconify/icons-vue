<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ud72a57ps.css';
import '../../css/b/byocr9c0k.css';
import '../../css/v/vj8lj592n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ud72a57ps"/><path class="byocr9c0k"/><path class="vj8lj592n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:social-buffer-outline" /></template>
