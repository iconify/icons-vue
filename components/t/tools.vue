<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5t20yy7y.css';
import '../../css/k/k662d66uk.css';
import '../../css/p/p1a-x02dg.css';
import '../../css/y/y8wsa_bcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="j5t20yy7y"/><path class="k662d66uk"/><path class="p1a-x02dg"/><path class="y8wsa_bcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:tools" /></template>
