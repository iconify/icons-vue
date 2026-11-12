<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iuhe4devu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iuhe4devu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:navigation-spark" /></template>
