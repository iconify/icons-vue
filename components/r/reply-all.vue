<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k0egs1bnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k0egs1bnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:reply-all" /></template>
