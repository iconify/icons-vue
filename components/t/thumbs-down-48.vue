<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_de_rbqi.css';
import '../../css/s/szwh8_usw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v_de_rbqi"/><path class="szwh8_usw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:thumbs-down-48" /></template>
