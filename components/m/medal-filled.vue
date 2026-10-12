<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uewhq319h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uewhq319h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:medal-filled" /></template>
