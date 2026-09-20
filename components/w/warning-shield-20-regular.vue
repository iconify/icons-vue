<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="a8qa91bmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:warning-shield-20-regular" /></template>
<style>
.a8qa91bmd {
  fill: currentColor;
  d: path("M15.12 10.963a.574.574 0 0 1 .76 0c.509.484 1.484 1.254 2.684 1.412c.239.032.436.212.436.438v2.11c0 2.839-2.783 3.87-3.386 4.06a.37.37 0 0 1-.227 0c-.602-.19-3.387-1.22-3.387-4.06v-2.11c0-.226.197-.407.437-.438c1.199-.158 2.175-.928 2.682-1.412M7.37 3.556c1.14-2.074 4.12-2.074 5.259 0l3.515 6.4a1.6 1.6 0 0 0-1.167-.05l-3.224-5.869c-.76-1.383-2.746-1.382-3.506 0L2.751 14.042c-.732 1.333.232 2.963 1.753 2.963h6.96c.18.375.403.707.647 1H4.504c-2.281 0-3.727-2.445-2.629-4.444zM10 12.75a.75.75 0 1 1-.001 1.501A.75.75 0 0 1 10 12.75m0-6.25a.5.5 0 0 1 .5.5v4a.501.501 0 0 1-1 0V7a.5.5 0 0 1 .5-.5");
}

</style>
