<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kiwqdl9ga.css';
import '../../css/g/gkmrzoxxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="kiwqdl9ga"/><path class="gkmrzoxxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:typeorm" /></template>
