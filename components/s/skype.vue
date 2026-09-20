<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dp90n_bdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dp90n_bdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:skype" /></template>
