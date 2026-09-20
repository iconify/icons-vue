<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5i1g5b_t.css';
import '../../css/c/crx0wqnqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q5i1g5b_t"/><path class="crx0wqnqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:mvl" /></template>
