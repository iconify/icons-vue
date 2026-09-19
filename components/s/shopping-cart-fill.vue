<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yjqkv_kki.css';
import '../../css/t/ttc468btu.css';
import '../../css/u/uii4avzkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yjqkv_kki"/><circle class="ttc468btu"/><circle class="uii4avzkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:shopping-cart-fill" /></template>
