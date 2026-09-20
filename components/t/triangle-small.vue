<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kn-xiyb0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kn-xiyb0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:triangle-small" /></template>
