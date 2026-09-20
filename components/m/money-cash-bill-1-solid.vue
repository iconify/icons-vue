<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nb9huobhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="nb9huobhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:money-cash-bill-1-solid" /></template>
