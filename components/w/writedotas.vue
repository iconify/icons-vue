<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2hk2mbes.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n2hk2mbes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:writedotas" /></template>
