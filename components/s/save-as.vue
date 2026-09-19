<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8na0-o0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="b8na0-o0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:save-as" /></template>
