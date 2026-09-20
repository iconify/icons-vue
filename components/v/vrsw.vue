<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGobVVib9E)" class="i4zwkwbkl"/><defs><linearGradient id="SVGobVVib9E" x1="3" x2="18.348" y1="7.656" y2="8" gradientUnits="userSpaceOnUse"><stop class="fwl_qbuqn"/><stop offset="1" class="qjx1lmbms"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:vrsw" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.fwl_qbuqn {
  stop-color: var(--svg-color--ff6900, #ff6900);
}

.i4zwkwbkl {
  d: path("M11.037 12.114c2.604-3.495 5.49-6.332 9.746-7.518a.2.2 0 0 1 .111 0a.25.25 0 0 1 .095.069l.011.032a.21.21 0 0 1-.111.18l-1.165.529c-2.276 1.059-4.537 3.88-5.945 6.914c-.699 1.504-1.392 2.901-2.075 4.553c-.09.212.074.413.285.418h1.573c.037 0 .026.01.026.032v2.022c0 .037-.01.064-.053.064c-1.932.01-4.277-.005-6.215 0c-.026 0-.053-.037-.064-.053a.12.12 0 0 1-.02-.069v-1.943c0-.042.02-.058.058-.058h1.493c.058 0 .11-.032.158-.069a.22.22 0 0 0 .064-.153a.8.8 0 0 0-.064-.329c-1.387-3.23-3-6.357-4.828-9.36c-.116-.196-.741-.148-1.016-.148A.095.095 0 0 1 3 7.132V5.168q0-.022.016-.037a.05.05 0 0 1 .042-.016h6.803l.016.021v2.006c0 .053-.021.09-.08.09h-.942a.17.17 0 0 0-.116.043a.18.18 0 0 0-.053.122c0 .074.01.142.042.211c.704 1.483 1.43 2.98 2.187 4.495c.037.069.074.069.122.01");
}

.qjx1lmbms {
  stop-color: var(--svg-color--f5430d, #f5430d);
}

</style>
