<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qzs4ogjnt.css';
import '../../css/n/n_w_i9mtx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qzs4ogjnt"/><path class="n_w_i9mtx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:shop-sign-bag-bold" /></template>
