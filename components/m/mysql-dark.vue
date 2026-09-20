<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hk3xrrbnq.css';
import '../../css/c/cjo_bouin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":252};
const content = `<path class="hk3xrrbnq"/><path class="cjo_bouin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:mysql-dark" /></template>
