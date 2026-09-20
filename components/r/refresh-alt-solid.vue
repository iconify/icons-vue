<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eq26h3bso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="eq26h3bso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:refresh-alt-solid" /></template>
