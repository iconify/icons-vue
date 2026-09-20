<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jos6di89e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="jos6di89e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:waste-basket-11" /></template>
