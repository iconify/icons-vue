<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eq8sbl5so.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eq8sbl5so"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:nurse" /></template>
