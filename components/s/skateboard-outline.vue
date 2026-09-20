<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k42iuqbqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k42iuqbqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:skateboard-outline" /></template>
