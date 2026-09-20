<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bv30cvl2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bv30cvl2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-rounded-x" /></template>
