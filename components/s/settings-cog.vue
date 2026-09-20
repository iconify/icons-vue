<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cnh1pz82n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cnh1pz82n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:settings-cog" /></template>
