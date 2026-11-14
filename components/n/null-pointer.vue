<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z_i5k0u8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:null-pointer" /></template>
<style>
.z_i5k0u8f {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m4.795 2.811l14 6q.068.029.129.071t.113.094q.051.053.092.115q.04.062.067.13q.028.069.041.142t.013.146q-.001.074-.016.146q-.016.073-.045.14q-.059.14-.169.245q-.109.106-.251.16l-6.189 2.38l-2.38 6.189q-.054.139-.156.248t-.239.168q-.137.061-.286.065t-.288-.05q-.157-.06-.273-.182q-.116-.121-.17-.281l-5-15q-.023-.07-.032-.143t-.004-.147t.025-.145t.052-.137t.079-.125q.045-.058.101-.107q.055-.048.12-.085q.064-.036.134-.06q.131-.043.268-.037q.138.005.264.06m9.596 11.58Q13 15.782 13 17.75t1.391 3.359T17.75 22.5t3.359-1.391T22.5 17.75t-1.391-3.359T17.75 13t-3.359 1.391m3.359.109q1.095 0 1.821.369l-4.702 4.702q-.369-.726-.369-1.821q0-3.25 3.25-3.25m0 6.5q-1.095 0-1.821-.369l4.702-4.702q.369.726.369 1.821Q21 21 17.75 21");
}

</style>
