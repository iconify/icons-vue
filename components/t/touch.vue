<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uh00ezddk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="uh00ezddk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:touch" /></template>
