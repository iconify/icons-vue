<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcvwldbnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wcvwldbnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shield-key-sharp" /></template>
