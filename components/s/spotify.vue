<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ge7sm6btc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ge7sm6btc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:spotify" /></template>
