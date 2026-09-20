<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":252};
const content = `<defs><linearGradient id="SVGEVUxfcrH" x1="64.26" x2="-2.269" y1="-38.457" y2="31.007" gradientTransform="scale(9.81654)" gradientUnits="userSpaceOnUse"><stop offset=".577" class="w9jk6_bvn"/><stop offset=".735" class="gxy08kbws"/><stop offset=".929" class="sg9t4g65w"/></linearGradient></defs><path fill="url(#SVGEVUxfcrH)" class="p6yh7126f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:stigg-icon" /></template>
<style>
.gxy08kbws {
  stop-color: var(--svg-color--92e759, #92e759);
}

.p6yh7126f {
  d: path("M186.814 241.623c-1.261.631-25.344 11.228-67.935 9.234c-22.189-1.048-41.435-5.141-55.106-8.919l73.721-85.416c13.144 3.357 30.076 6.506 49.32 7.45c42.593 2.099 66.674-8.605 67.936-9.234l-67.936 86.989zM76.709 77.506C64.614 36.688 69.347 10.873 69.662 9.51L1.096 95.976c-.21 1.363-4.943 27.178 7.045 67.996c6.31 21.198 14.828 38.932 21.769 51.314l65.728-91.609c-6.31-11.962-13.461-27.701-18.929-46.065zm170.89 9.025c-9.674-32.74-24.819-56.978-31.022-66.214l-60.996 77.547l11.464 54.88c6.834.944 13.565 1.573 20.4 1.994c3.47.104 6.942.21 10.307.21c33.021 0 51.425-7.764 53.423-8.708l4.733-2.101c.421-11.332-.317-31.375-8.203-57.714zm-38.28-71.774C198.908 10.873 171.776 1.953 137.598.276c-27.447-1.365-47.114 2.623-58.05 5.77l-.948 5.037c-.21 1.05-4.416 25.499 6.837 63.801c1.893 6.504 4.206 12.906 6.73 19.308l56.157-1.89l61.101-77.441z");
}

.sg9t4g65w {
  stop-color: var(--svg-color--69fff1, #69fff1);
}

.w9jk6_bvn {
  stop-color: var(--svg-color--f9f8f5, #f9f8f5);
}

</style>
