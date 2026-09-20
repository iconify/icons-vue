<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8k8y42th.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q8k8y42th"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:thumbs-down-fill" /></template>
