<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b__u3zbwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b__u3zbwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:shield-cancel" /></template>
