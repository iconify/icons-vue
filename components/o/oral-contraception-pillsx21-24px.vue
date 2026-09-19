<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dax_enbck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dax_enbck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:oral-contraception-pillsx21-24px" /></template>
