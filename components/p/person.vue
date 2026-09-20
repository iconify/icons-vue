<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/efx4t9bgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="efx4t9bgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:person" /></template>
