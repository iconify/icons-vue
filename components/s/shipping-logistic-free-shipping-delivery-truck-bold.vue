<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q--72vv7c.css';
import '../../css/c/cz0r6uwoz.css';
import '../../css/n/nf5-akdhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q--72vv7c"/><path class="cz0r6uwoz"/><path class="nf5-akdhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:shipping-logistic-free-shipping-delivery-truck-bold" /></template>
