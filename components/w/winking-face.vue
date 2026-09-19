<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhzkfkbjg.css';
import '../../css/b/b0u2a7nui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lhzkfkbjg"/><path clip-rule="evenodd" class="b0u2a7nui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:winking-face" /></template>
