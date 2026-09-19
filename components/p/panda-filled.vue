<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kl-up0lit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kl-up0lit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:panda-filled" /></template>
