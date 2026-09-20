<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pht41zbla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pht41zbla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sun-dim-sharp-fill" /></template>
