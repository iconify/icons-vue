<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swhag75sb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="swhag75sb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:plane-sharp-fill" /></template>
