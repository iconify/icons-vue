<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eb7672bzg.css';
import '../../css/e/eyk4iwcnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eb7672bzg"/><path class="eyk4iwcnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:vee" /></template>
