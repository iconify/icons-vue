<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-x6_p_np.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a-x6_p_np"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:not-superset-of" /></template>
