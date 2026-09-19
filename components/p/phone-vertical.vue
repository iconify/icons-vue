<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ejkle9bys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ejkle9bys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:phone-vertical" /></template>
