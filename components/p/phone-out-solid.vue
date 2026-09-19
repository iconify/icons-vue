<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mu-d01bjj.css';
import '../../css/n/nm2dxfjpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mu-d01bjj"/><path class="nm2dxfjpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:phone-out-solid" /></template>
