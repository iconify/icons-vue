<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jr_ntm2dn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jr_ntm2dn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:sort-amount-up" /></template>
