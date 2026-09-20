<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmulxe3id.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mmulxe3id"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:thumb-up-line" /></template>
