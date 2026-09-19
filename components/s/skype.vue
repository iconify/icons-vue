<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s810i2bye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s810i2bye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:skype" /></template>
