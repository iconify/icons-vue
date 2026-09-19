<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/som_9bofx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="som_9bofx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontelico:spin3" /></template>
