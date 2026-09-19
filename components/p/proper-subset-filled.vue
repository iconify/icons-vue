<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zfn1or_0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zfn1or_0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:proper-subset-filled" /></template>
