<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-wru_mwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f-wru_mwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:shield-alert-fill" /></template>
