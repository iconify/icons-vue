<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f7uf5i4hv.css';
import '../../css/s/sgq0p14ld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f7uf5i4hv"/><circle class="sgq0p14ld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:user-fill" /></template>
