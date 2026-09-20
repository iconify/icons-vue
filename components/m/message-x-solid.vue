<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3nk_yjdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="c3nk_yjdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:message-x-solid" /></template>
