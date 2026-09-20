<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fr1ba6b2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="fr1ba6b2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:mobile" /></template>
