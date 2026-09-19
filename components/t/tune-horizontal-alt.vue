<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezdp1hbyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ezdp1hbyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:tune-horizontal-alt" /></template>
