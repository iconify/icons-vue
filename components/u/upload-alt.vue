<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/okq_komxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="okq_komxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:upload-alt" /></template>
