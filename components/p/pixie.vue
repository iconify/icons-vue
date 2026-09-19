<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ejfcwgjrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="ejfcwgjrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:pixie" /></template>
