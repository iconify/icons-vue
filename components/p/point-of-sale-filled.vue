<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi-9byb8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bi-9byb8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:point-of-sale-filled" /></template>
