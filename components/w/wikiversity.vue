<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_pd63qht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v_pd63qht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:wikiversity" /></template>
