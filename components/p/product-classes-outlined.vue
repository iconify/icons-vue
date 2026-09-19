<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/egw0_e_yk.css';
import '../../css/g/grhwfqo-l.css';
import '../../css/u/uxmpfhdsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="egw0_e_yk"/><path class="grhwfqo-l"/><path class="uxmpfhdsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:product-classes-outlined" /></template>
