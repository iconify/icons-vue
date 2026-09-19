<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oc0r1lbas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oc0r1lbas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:phone-forward-filled" /></template>
