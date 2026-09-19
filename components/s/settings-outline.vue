<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_c0fnb5t.css';
import '../../css/x/xk9zeubkp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d_c0fnb5t"/><path class="xk9zeubkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:settings-outline" /></template>
