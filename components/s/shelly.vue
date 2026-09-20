<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/blubov6ot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="blubov6ot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:shelly" /></template>
