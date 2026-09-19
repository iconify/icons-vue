<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bb39ecbvy.css';
import '../../css/f/f3eag6bdv.css';
import '../../css/j/jdf9bpbui.css';
import '../../css/x/xi8ki5c4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="bb39ecbvy"/><path class="f3eag6bdv"/><path class="jdf9bpbui"/><path class="xi8ki5c4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:red-envelope-twotone" /></template>
