<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/evfd4hbar.css';
import '../../css/l/lt9r55aoa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="evfd4hbar"/><path class="lt9r55aoa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:startups" /></template>
