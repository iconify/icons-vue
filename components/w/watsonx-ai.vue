<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6vzv4bqp.css';
import '../../css/s/s3ckdxwss.css';
import '../../css/v/vbagb8yxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="v6vzv4bqp"/><path class="s3ckdxwss"/><path class="vbagb8yxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:watsonx-ai" /></template>
