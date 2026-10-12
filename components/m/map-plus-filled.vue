<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qb2gh7q5f.css';
import '../../css/g/gadlesbca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qb2gh7q5f"/><path clip-rule="evenodd" class="gadlesbca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:map-plus-filled" /></template>
