<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lg7n2eb4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":182,"height":981};
const content = `<path class="lg7n2eb4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:parenright" /></template>
