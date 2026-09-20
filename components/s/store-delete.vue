<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3dmyjhyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k3dmyjhyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:store-delete" /></template>
