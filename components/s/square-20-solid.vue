<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqq6_yapo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="eqq6_yapo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:square-20-solid" /></template>
