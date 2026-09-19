<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jvbubjb1v.css';
import '../../css/m/mh-rg_bsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jvbubjb1v"/><path class="mh-rg_bsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:phone-incoming" /></template>
