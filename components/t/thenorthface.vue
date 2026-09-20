<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1ya5py-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f1ya5py-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:thenorthface" /></template>
