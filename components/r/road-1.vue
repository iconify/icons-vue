<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nl6h39t1z.css';
import '../../css/b/b9iubibxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nl6h39t1z"/><path clip-rule="evenodd" class="b9iubibxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:road-1" /></template>
