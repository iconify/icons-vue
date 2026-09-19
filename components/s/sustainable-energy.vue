<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/acpw8s-ch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="acpw8s-ch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:sustainable-energy" /></template>
