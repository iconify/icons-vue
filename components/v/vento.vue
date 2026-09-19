<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nv5zpjb7q.css';
import '../../css/z/zpye_6bpo.css';
import '../../css/c/cq1cnpxnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nv5zpjb7q"/><path class="zpye_6bpo"/><path class="cq1cnpxnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:vento" /></template>
