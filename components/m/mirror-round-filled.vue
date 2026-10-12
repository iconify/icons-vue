<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/otyqlnb_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="otyqlnb_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:mirror-round-filled" /></template>
