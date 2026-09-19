<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfa17oyjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="mfa17oyjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:mountain" /></template>
