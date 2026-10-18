<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ckmbmabfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ckmbmabfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:qr-code" /></template>
