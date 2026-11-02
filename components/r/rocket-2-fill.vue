<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/br_smg_dn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="br_smg_dn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rocket-2-fill" /></template>
