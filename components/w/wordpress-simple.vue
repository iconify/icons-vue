<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kw6ui7bhy.css';
import '../../css/s/syf0cfsom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="kw6ui7bhy"/><path class="syf0cfsom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:wordpress-simple" /></template>
