<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o1yy3pmfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o1yy3pmfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:some-tommelopp" /></template>
