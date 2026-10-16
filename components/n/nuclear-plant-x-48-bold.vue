<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vi1_s4oue.css';
import '../../css/a/a-1g_ibpd.css';
import '../../css/s/sfb8rqn9v.css';
import '../../css/k/ksydp3lsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vi1_s4oue"/><path class="a-1g_ibpd"/><path class="sfb8rqn9v"/><path class="ksydp3lsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:nuclear-plant-x-48-bold" /></template>
