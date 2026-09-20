<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sngv2ac6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sngv2ac6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:subscription-list-solid" /></template>
