<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbma2iban.css';
import '../../css/f/fv36o8gan.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sbma2iban"/><path class="fv36o8gan"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:warehouse-cart-packages-2-bold" /></template>
