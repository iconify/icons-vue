<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bubclra3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bubclra3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:text-slash-solid" /></template>
