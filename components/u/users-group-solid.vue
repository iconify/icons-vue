<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6kppccdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s6kppccdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:users-group-solid" /></template>
