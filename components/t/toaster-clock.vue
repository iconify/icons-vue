<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k8n4n_jvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k8n4n_jvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:toaster-clock" /></template>
