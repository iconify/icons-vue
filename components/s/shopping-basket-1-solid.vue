<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bb60eqbtz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="bb60eqbtz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:shopping-basket-1-solid" /></template>
