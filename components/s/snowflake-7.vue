<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lalqpdp_l.css';
import '../../css/f/f8sr_ibol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":24};
const content = `<path class="lalqpdp_l"/><path class="f8sr_ibol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:snowflake-7" /></template>
