<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdrolvo7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="mdrolvo7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:test-explore-solid" /></template>
