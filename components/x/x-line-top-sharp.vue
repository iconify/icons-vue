<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-k3mlf4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-k3mlf4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:x-line-top-sharp" /></template>
