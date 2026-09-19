<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/krb-eh9nj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="krb-eh9nj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:square-filled" /></template>
