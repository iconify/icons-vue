<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9ev1ybyr.css';
import '../../css/q/qwm5tjbfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s9ev1ybyr"/><path class="qwm5tjbfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:upp" /></template>
