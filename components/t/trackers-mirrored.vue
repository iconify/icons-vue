<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/em3b8vi0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="em3b8vi0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:trackers-mirrored" /></template>
