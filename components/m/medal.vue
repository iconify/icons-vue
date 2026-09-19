<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gf-21-0mo.css';
import '../../css/d/dum7nab_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gf-21-0mo"/><path class="dum7nab_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:medal" /></template>
