<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/autq6ssyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="autq6ssyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:pointer-pin" /></template>
