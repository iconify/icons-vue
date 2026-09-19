<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j89ezbb6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j89ezbb6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:postnl" /></template>
