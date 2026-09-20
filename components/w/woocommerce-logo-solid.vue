<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmzecqb4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mmzecqb4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:woocommerce-logo-solid" /></template>
