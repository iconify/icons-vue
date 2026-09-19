<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-50yz2xi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":478,"height":512};
const content = `<path clip-rule="evenodd" class="b-50yz2xi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:ngrx" /></template>
