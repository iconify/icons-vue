<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csr1j5bxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="csr1j5bxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:minus-circle" /></template>
