<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbi2j8bjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jbi2j8bjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:search-plus-sharp" /></template>
