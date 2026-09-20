<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nb5qhfflw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nb5qhfflw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:playstation4" /></template>
