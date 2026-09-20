<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h068x0bdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h068x0bdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:redhat" /></template>
