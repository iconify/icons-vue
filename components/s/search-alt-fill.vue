<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ibq2rdfwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ibq2rdfwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:search-alt-fill" /></template>
