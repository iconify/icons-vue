<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ii5_mrmvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ii5_mrmvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:monitor-edit" /></template>
