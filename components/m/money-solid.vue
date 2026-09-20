<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gu5lx12xc.css';
import '../../css/v/v3045wb7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gu5lx12xc"/><path clip-rule="evenodd" class="v3045wb7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:money-solid" /></template>
